<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt4qdxb4y.css';
import '../../css/x/xoqcm6b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bt4qdxb4y"/><path class="xoqcm6b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-edit" /></template>
