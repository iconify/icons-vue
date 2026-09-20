<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw3g42-7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ward-outline-sharp" /></template>
<style>
.nw3g42-7a {
  fill: currentColor;
  d: path("M5.116 4h-2V3h3v18h-1zm2.769 17V3h11v18zm1-9.206q.392-.39.902-.592T10.884 11h5q.589 0 1.099.202t.901.592V4h-9zm3.433-3.228q-.433-.433-.433-1.066t.433-1.066Q12.752 6 13.385 6q.632 0 1.066.434q.434.433.434 1.066t-.434 1.066T13.385 9t-1.067-.434M8.885 20h9v-6q0-.825-.588-1.412T15.885 12h-5q-.825 0-1.413.588T8.885 14zm4-1.5h1v-2h2v-1h-2v-2h-1v2h-2v1h2zm-4 1.5h9z");
}

</style>
