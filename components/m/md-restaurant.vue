<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn-6hubiu.css';
import '../../css/w/w59lw5byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vn-6hubiu"/><path class="w59lw5byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-restaurant" /></template>
