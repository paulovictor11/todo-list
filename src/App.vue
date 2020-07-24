<template>
    <div id="app">
        <section class="hero is-primary is-bold is-fullheight">

            <div class="hero-head">
                <nav class="navbar">
                    <div class="container">
                        <div class="navbar-brand">
                            <a class="navbar-item">VueJs Tutorial 1.0</a>
                        </div>
                    </div>
                </nav>
            </div>

            <div class="hero-body">
                <div class="container has-text-centered">
                    <div class="row">
                        <div class="columns">
                            <div class="column is-half is-offset-one-quarter">
                                <TodoCard></TodoCard>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="hero-foot">
                <div class="container">
                    <div class="content has-text-centered">
                        <p>
                            <strong>VueJs Tutorial</strong> by Paulo Victor.
                        </p>
                    </div>
                </div>
            </div>

        </section>
    </div>
</template>

<script>
    import TodoCard from "./components/TodoCard";

    export default {
        name: 'app',
        components: {
          TodoCard
        },
        data () {
            return {
                msg: 'Hello, World!'
            }
        }
    }
</script>

<style>

</style>
