<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qh22lf0ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-16-filled" /></template>
<style>
.qh22lf0ai {
  fill: currentColor;
  d: path("M7.5 9a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .5-.5M12 9a3 3 0 0 1 2.443 4.736l.41.41a.5.5 0 1 1-.707.707l-.41-.41c-.49.35-1.088.557-1.736.557a3 3 0 0 1 0-6m-1-6.484a1.5 1.5 0 0 1 1.5 0l1.25.721A2.5 2.5 0 0 1 15 5.401v3.954A4 4 0 0 0 12 8a4 4 0 0 0-3.008 1.363A1.499 1.499 0 0 0 6 9.5v5q.001.248.076.472l-.33-.19A1.5 1.5 0 0 1 5 13.484v-6.64c0-.535.286-1.031.75-1.3zM12 10a2 2 0 1 0 0 4c.37 0 .716-.104 1.014-.28l-.867-.867a.5.5 0 1 1 .707-.707l.867.868A2 2 0 0 0 12 10M6.75.639a2.5 2.5 0 0 1 2.5 0l1.519.877a3 3 0 0 0-.269.133L5.25 4.681A2.5 2.5 0 0 0 4 6.846v6.64q0 .15.019.298L2.25 12.763A2.5 2.5 0 0 1 1 10.598V5.4a2.5 2.5 0 0 1 1.25-2.165z");
}

</style>
