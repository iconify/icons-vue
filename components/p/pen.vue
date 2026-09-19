<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhwd7iqio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="lhwd7iqio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pen" /></template>
