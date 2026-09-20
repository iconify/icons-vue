<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pdafjwb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tag-error-16-filled" /></template>
<style>
.pdafjwb4i {
  fill: currentColor;
  d: path("M1.536 6.327L6.296 1.6a2.02 2.02 0 0 1 1.415-.585L10.975 1a2.007 2.007 0 0 1 2.021 2.014l-.019 2.574a5.5 5.5 0 0 0-7.428 7.31a2 2 0 0 1-.703-.454l-3.31-3.288a1.99 1.99 0 0 1 0-2.829m7.728-1.669a.774.774 0 0 0 1.09 0c.3-.298.3-.783 0-1.082a.774.774 0 0 0-1.09 0c-.3.3-.3.784 0 1.082M15 10.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0M10.5 8a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 1 0v-2a.5.5 0 0 0-.5-.5m0 5.125a.625.625 0 1 0 0-1.25a.625.625 0 0 0 0 1.25");
}

</style>
