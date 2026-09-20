<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yig-g3btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yig-g3btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:wave" /></template>
