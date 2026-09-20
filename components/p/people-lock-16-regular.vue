<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b37v31n3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-lock-16-regular" /></template>
<style>
.b37v31n3s {
  fill: currentColor;
  d: path("M12.5 7a2 2 0 0 1 2 2v1h.5a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h.5V9a2 2 0 0 1 2-2m0 5.25a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M7.5 8c.792 0 1.474.46 1.798 1.128c-.33.123-.618.33-.838.597A1 1 0 0 0 7.5 9h-5a1 1 0 0 0-1 1c0 .508.304.992.932 1.375S3.966 12 5 12s1.94-.242 2.568-.625q.25-.154.432-.327v1.232c-.808.466-1.867.72-3 .72c-1.175 0-2.27-.272-3.089-.77C1.091 11.73.5 10.965.5 10a2 2 0 0 1 2-2zm5 0a1 1 0 0 0-1 1v1h2V9a1 1 0 0 0-1-1M5 1.5A2.75 2.75 0 1 1 5 7a2.75 2.75 0 0 1 0-5.5m7.231 1.009a2.253 2.253 0 0 1 2.023 2.24l-.012.23a2.24 2.24 0 0 1-.558 1.263A3 3 0 0 0 12.5 6c-.67 0-1.289.222-1.788.594a2.25 2.25 0 0 1-.95-1.615l-.012-.23a2.25 2.25 0 0 1 2.252-2.252zm-.229.988a1.252 1.252 0 1 0 0 2.504a1.252 1.252 0 0 0 0-2.504M5 2.5A1.75 1.75 0 1 0 5 6a1.75 1.75 0 0 0 0-3.5");
}

</style>
