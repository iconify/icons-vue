<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7giafb7e.css';
import '../../css/a/az0bq2bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="e7giafb7e"/><path class="az0bq2bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:ok" /></template>
