<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-rrbjbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-off-24-regular" /></template>
<style>
.i-rrbjbmi {
  fill: currentColor;
  d: path("M5.454 6.515L2.22 3.28a.75.75 0 1 1 1.06-1.06l18.5 18.5a.75.75 0 0 1-1.06 1.06L17 18.06v3.19a.75.75 0 0 1-1.093.668l-.09-.055L12 19.176l-3.816 2.687a.75.75 0 0 1-1.175-.508L7 21.25l-.002-7.352A6.98 6.98 0 0 1 5 9c0-.875.16-1.713.454-2.485M15.499 16.56l-1.014-1.014A7 7 0 0 1 12 16c-1.275 0-2.47-.34-3.5-.936v4.74l3.067-2.159a.75.75 0 0 1 .763-.06l.1.06l3.07 2.16zm-2.211-2.211L6.652 7.712a5.5 5.5 0 0 0 6.636 6.636M17.5 9c0 1.473-.579 2.81-1.521 3.797l1.06 1.061A7 7 0 0 0 7.142 3.96l1.062 1.061A5.5 5.5 0 0 1 17.5 9");
}

</style>
