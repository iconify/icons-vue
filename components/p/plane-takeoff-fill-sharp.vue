<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsxpfyknk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-fill-sharp" /></template>
<style>
.hsxpfyknk {
  fill: currentColor;
  d: path("m17.707 8.707l-1.636 1.636l.915 5.493a1 1 0 0 1-.279.871l-1 1A.998.998 0 0 1 14.2 17.6l-2.499-3.332l-.701.35V16c0 .265-.105.52-.293.707l-1 1a1 1 0 0 1-1.414 0l-4-4a1 1 0 0 1 0-1.414l1-1A1 1 0 0 1 6 11h1.382l.35-.701L4.4 7.8a.998.998 0 0 1-.107-1.507l1-1a1 1 0 0 1 .871-.279l5.493.915l1.636-1.636c.77-.771 1.784-1.678 2.886-1.899c.99-.197 1.836.207 2.528.899c1.951 1.952.536 3.878-1 5.414M21 20a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
