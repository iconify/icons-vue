<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pr7bfu0oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pen-sync-16-regular" /></template>
<style>
.pr7bfu0oq {
  fill: currentColor;
  d: path("M12.44 1.56a1.914 1.914 0 0 0-2.707 0L2.338 8.956a1.65 1.65 0 0 0-.398.644l-.914 2.743a.5.5 0 0 0 .632.633l2.743-.915c.243-.08.463-.217.644-.398l.065-.064a5.5 5.5 0 0 1-.106-1.309l-.666.666a.65.65 0 0 1-.253.157l-1.794.598l.598-1.794a.65.65 0 0 1 .156-.254l7.395-7.394a.914.914 0 1 1 1.293 1.293L10.29 5.004a5.6 5.6 0 0 1 1.31.106l.841-.842a1.914 1.914 0 0 0 0-2.707M6 10.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 0 0-9 0m6.5-3a.5.5 0 0 1 .5.5v1.5a.5.5 0 0 1-.5.5H11a.5.5 0 0 1 0-1h.468a2 2 0 0 0-.933-.25a2 2 0 0 0-1.45.586a.5.5 0 0 1-.706-.707A3 3 0 0 1 12 8.152V8a.5.5 0 0 1 .5-.5m-.876 5.532A3 3 0 0 1 9 12.848V13a.5.5 0 0 1-1 0v-1.5a.5.5 0 0 1 .5-.5H10a.5.5 0 0 1 0 1h-.468a2 2 0 0 0 .933.25a2 2 0 0 0 1.45-.586a.5.5 0 0 1 .706.707c-.285.285-.624.51-.997.66");
}

</style>
