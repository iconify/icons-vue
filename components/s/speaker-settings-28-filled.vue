<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="g4wohjb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:speaker-settings-28-filled" /></template>
<style>
.g4wohjb3q {
  fill: currentColor;
  d: path("M14.395 3.838c.798-.743 2.105-.181 2.105.906v9.403a7.49 7.49 0 0 0-3.5 6.34c0 .882.152 1.728.432 2.513l-3.974-3.698a1.76 1.76 0 0 0-1.196-.47H5.25c-1.795 0-3.25-1.445-3.25-3.228v-3.469c0-1.783 1.455-3.228 3.25-3.228h3.011c.445 0 .873-.168 1.197-.47zm2.401 12.86a2 2 0 0 1-1.441 2.496l-1.024.254a6.8 6.8 0 0 0 .008 2.152l.976.235a2 2 0 0 1 1.45 2.51l-.324 1.098a6.2 6.2 0 0 0 1.753 1.1l.843-.886a2 2 0 0 1 2.899 0l.85.895a6.2 6.2 0 0 0 1.751-1.09l-.335-1.16a2 2 0 0 1 1.441-2.496l1.026-.253a6.8 6.8 0 0 0-.008-2.152l-.977-.235a2 2 0 0 1-1.45-2.51l.324-1.1a6.2 6.2 0 0 0-1.753-1.1l-.843.888a2 2 0 0 1-2.9 0l-.849-.895a6.2 6.2 0 0 0-1.751 1.09zM20.5 22a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3");
}

</style>
