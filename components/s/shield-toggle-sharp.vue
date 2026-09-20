<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0pjmubzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shield-toggle-sharp" /></template>
<style>
.v0pjmubzb {
  fill: currentColor;
  d: path("M10.402 10.98h3.189q.657 0 1.13-.467q.471-.467.471-1.124t-.468-1.128t-1.126-.472H10.41q-.658 0-1.13.467q-.472.468-.472 1.124t.468 1.129t1.126.472m2.77-1.075q-.21-.21-.21-.52t.21-.521t.52-.211t.52.21t.211.52t-.21.52q-.21.212-.52.212t-.521-.21m-2.77 5.306h3.189q.657 0 1.13-.468q.471-.467.471-1.124t-.468-1.129t-1.126-.472H10.41q-.658 0-1.13.468q-.472.467-.472 1.124t.468 1.128t1.126.472m-.614-1.075q-.211-.21-.211-.52t.21-.52q.21-.212.52-.212t.521.21q.21.21.21.52t-.21.522t-.52.21t-.52-.21M12 20.962q-3.014-.895-5.007-3.651T5 11.1V5.692l7-2.615l7 2.615V11.1q0 3.454-1.993 6.21T12 20.963");
}

</style>
