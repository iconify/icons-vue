<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pzdn14jke"/><path class="n16re07-t"/><path class="yo4gu2krf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:pushpin" /></template>
<style>
.n16re07-t {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M24.46 28.298L46.873 5.883L58.33 17.338L35.914 39.753z");
}

.pzdn14jke {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M24.5 35.5C17.8 42.9 2.9 60.9.6 63.1c0 0-.1 0-.1.1c-.9.9-.6 1.2.3.3c2-2 20.2-17.2 27.6-23.9z");
}

.yo4gu2krf {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M43.6 54.6c.9-7.8-2.5-17.1-9.8-24.3S17.2 19.6 9.4 20.4zM64 22.9c-5.2.6-11.4-1.7-16.3-6.6S40.5 5.2 41.1 0z");
}

</style>
