<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq1u45bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:watch-lock" /></template>
<style>
.yq1u45bzm {
  fill: currentColor;
  d: path("M10.73 14.462q-.359 0-.602-.24q-.244-.24-.244-.6v-2.118q0-.36.244-.604q.243-.244.603-.244v-.847q0-.53.37-.9t.899-.37t.895.37t.367.899v.846q.355 0 .604.249q.25.249.25.597v2.116q0 .359-.25.602q-.249.244-.597.244zm.741-3.808h1.058v-.846q0-.217-.156-.373T12 9.279t-.373.156t-.156.373zM9.961 21l-1.119-3.934q-1.258-.739-2.05-2.087T6 12t.792-2.979t2.05-2.087L9.962 3h4.077l1.119 3.935q1.258.738 2.05 2.086T18 12t-.792 2.979t-2.05 2.087L14.038 21zm5.577-5.462Q17 14.075 17 12t-1.463-3.537T12 7T8.463 8.463T7 12t1.463 3.538T12 17t3.538-1.463");
}

</style>
