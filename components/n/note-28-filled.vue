<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ii9m521qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:note-28-filled" /></template>
<style>
.ii9m521qy {
  fill: currentColor;
  d: path("M3 6.75A3.75 3.75 0 0 1 6.75 3h14.5A3.75 3.75 0 0 1 25 6.75V15h-6.25A3.75 3.75 0 0 0 15 18.75V25H6.75A3.75 3.75 0 0 1 3 21.25zM16.5 25h.06L25 16.56v-.06h-6.25a2.25 2.25 0 0 0-2.25 2.25z");
}

</style>
