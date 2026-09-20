<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt-zk8blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qt-zk8blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mineshaft-cage" /></template>
