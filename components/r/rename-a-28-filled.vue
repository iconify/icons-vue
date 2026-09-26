<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="q5j24l8zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-a-28-filled" /></template>
<style>
.q5j24l8zb {
  fill: currentColor;
  d: path("M20.25 2a.75.75 0 0 1 0 1.5h-1.752v21h1.752a.75.75 0 0 1 0 1.5h-5a.75.75 0 0 1 0-1.5h1.748v-21H15.25a.75.75 0 0 1 0-1.5zm-9.6 12h-3.3L9 10.505zm5.348 9H5.75A3.75 3.75 0 0 1 2 19.25V8.75A3.75 3.75 0 0 1 5.75 5h10.248zM9 8a.75.75 0 0 0-.625.336l-.053.094l-4.25 9a.75.75 0 1 0 1.356.64l1.214-2.57h4.716l1.214 2.57a.75.75 0 1 0 1.356-.64l-4.25-9A.75.75 0 0 0 9 8m13.25-3A3.75 3.75 0 0 1 26 8.75v10.5A3.75 3.75 0 0 1 22.25 23h-2.752V5z");
}

</style>
