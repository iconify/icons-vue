<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrjnvkbuz.css';
import '../../css/t/t3uv5kdfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lrjnvkbuz"/><path class="t3uv5kdfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tariff-48" /></template>
