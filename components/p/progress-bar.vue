<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwc03jzoe.css';
import '../../css/z/zalphcmjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nwc03jzoe"/><path class="zalphcmjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:progress-bar" /></template>
