<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx6gsqdoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qx6gsqdoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:reorder-three-outline" /></template>
