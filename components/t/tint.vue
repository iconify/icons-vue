<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qghl1qx4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="qghl1qx4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tint" /></template>
