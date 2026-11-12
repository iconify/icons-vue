<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm366-d-x.css';
import '../../css/j/jutyogb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wm366-d-x"/><path class="jutyogb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maildev-dark" /></template>
