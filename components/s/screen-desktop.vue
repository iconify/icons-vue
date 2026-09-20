<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5qruj8rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r5qruj8rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:screen-desktop" /></template>
