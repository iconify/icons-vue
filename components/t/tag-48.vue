<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrjnvkbuz.css';
import '../../css/n/nl3t421aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lrjnvkbuz"/><path class="nl3t421aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tag-48" /></template>
