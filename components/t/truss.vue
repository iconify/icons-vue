<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thv1-lbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:truss" /></template>
<style>
.thv1-lbyp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m1.796 18.243l4.75-13q.038-.106.106-.196q.069-.09.16-.156q.092-.066.198-.102t.22-.039h9.52q.133 0 .257.046q.156.056.273.174t.174.273l4.75 13q.043.116.046.24v.017q0 .115-.035.225q-.034.11-.1.205t-.158.165t-.2.109q-.116.043-.24.046H2.5q-.133 0-.257-.046q-.106-.038-.196-.106q-.09-.069-.156-.16q-.066-.092-.102-.198t-.039-.22v-.02q0-.133.046-.257M12 16.315L15.677 6.25H8.323zM3.573 17.75h7.354L7.25 7.685zM16.75 7.685L13.073 17.75h7.354z");
}

</style>
