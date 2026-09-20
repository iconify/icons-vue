<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sgvpq630e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-chat-16-regular" /></template>
<style>
.sgvpq630e {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1-2.182 8.437l-1.789.544a.41.41 0 0 1-.51-.51l.544-1.79A4.5 4.5 0 0 1 11.5 7M7.259 8a5.5 5.5 0 0 0-.656 1H2.5a1 1 0 0 0-1 1c0 .508.304.992.932 1.375S3.966 12 5 12c.357 0 .698-.031 1.018-.085q.038.508.164.986C5.802 12.964 5.406 13 5 13c-1.175 0-2.27-.272-3.089-.77C1.091 11.73.5 10.965.5 10a2 2 0 0 1 2-2zM9.5 12a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zm0-2a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zM5 1.5A2.75 2.75 0 1 1 5 7a2.75 2.75 0 0 1 0-5.5m6.731 1.009a2.253 2.253 0 0 1 2.023 2.24l-.012.23c-.05.49-.259.933-.572 1.279A5.5 5.5 0 0 0 11.514 6a1.252 1.252 0 1 0-.026 0a5.5 5.5 0 0 0-1.656.258a2.24 2.24 0 0 1-.57-1.28L9.25 4.75a2.25 2.25 0 0 1 2.252-2.252zM5 2.5A1.75 1.75 0 1 0 5 6a1.75 1.75 0 0 0 0-3.5");
}

</style>
