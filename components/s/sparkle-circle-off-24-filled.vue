<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucz7febcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-circle-off-24-filled" /></template>
<style>
.ucz7febcf {
  fill: currentColor;
  d: path("M20.72 2.22a.75.75 0 1 1 1.06 1.06l-2.2 2.2A9.96 9.96 0 0 1 22 12c0 5.523-4.477 10-10 10a9.96 9.96 0 0 1-6.52-2.42l-2.2 2.2a.75.75 0 0 1-1.06-1.06zm-4.772 10.486c-.282-.94-1.614-.941-1.896 0l-.18.598a.85.85 0 0 1-.57.569l-.597.18c-.94.282-.94 1.614.001 1.896l.596.179a.85.85 0 0 1 .57.57l.18.599c.282.94 1.615.94 1.897-.001l.179-.597a.85.85 0 0 1 .57-.57l.598-.18c.94-.282.94-1.614 0-1.896l-.599-.18a.85.85 0 0 1-.57-.57zM12 2a9.95 9.95 0 0 1 5.298 1.52L12.41 8.407l-.869-.307a1.05 1.05 0 0 1-.639-.64l-.459-1.294c-.314-.888-1.571-.888-1.885.001L8.1 7.46a1.05 1.05 0 0 1-.64.64l-1.294.458c-.889.314-.889 1.571 0 1.885l1.294.457c.299.106.534.342.64.641l.306.87l-4.887 4.887A9.95 9.95 0 0 1 2 12C2 6.477 6.477 2 12 2");
}

</style>
