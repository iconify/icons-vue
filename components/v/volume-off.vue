<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgr529r6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qgr529r6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:volume-off" /></template>
