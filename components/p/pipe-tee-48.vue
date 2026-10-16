<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3hnj1bgs.css';
import '../../css/n/ng_3h1b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g3hnj1bgs"/><path class="ng_3h1b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-tee-48" /></template>
