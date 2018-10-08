<template>
    <div>
        <div class="card mb-3">
            <div class="card-body">
                <h5 class="card-title mb-3">{{ blogtitle }}</h5>
                <h6 class="card-subtitle mb-3 text-muted">{{ blogcreated }}</h6>
                <p class="card-text mb-3">{{ blogbody }}</p>
            </div>
            <div class="card-body">
                <p class="font-weight-bold text-left">Comments</p>
                <p class="card-text text-left mb-3"><span class="badge badge-pill badge-success">1</span> {{ blogcomment[0].body }}</p>
                <p class="card-text text-left mb-3"><span class="badge badge-pill badge-success">2</span> {{ blogcomment[1].body }}</p>
                <p class="card-text text-left mb-3"><span class="badge badge-pill badge-success">3</span> {{ blogcomment[2].body }}</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props: ['blogindex', 'blogtitle', 'blogbody', 'blogcreated', 'blogcomment'],
}
</script>

<style>

</style>

