<template>
    <div
      class="entry-container mb-3 p-2 pointer"
      @click="$router.push({name: 'entry', params: {id: 1}})">
        <div class="entry-tittle d-flex">
            <span class="text-success fs-5 fw-bold">13</span>
            <span class="mx-1 fs-5">Noviembre</span>
            <span class="mx-2 fw-light">2023, lunes</span>
        </div>

        <div class="entry-description">
            Laboris sit occaecat duis quis cupidatat ipsum sit in labore. Nulla officia sunt ea non proident laboris excepteur eiusmod aliqua adipisicing sint qui nisi. Ullamco sit cillum nisi nulla excepteur ullamco sint esse fugiat amet. Incididunt dolore aute ad aliquip non ipsum velit elit occaecat ipsum commodo duis. Id voluptate amet do ex occaecat pariatur eiusmod laboris aliqua voluptate Lorem. Reprehenderit anim adipisicing eiusmod in duis fugiat qui pariatur deserunt nulla laborum. Pariatur deserunt sint aute exercitation et dolore magna aliquip.
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-description{
        font-size: 12px;
    }
}
</style>