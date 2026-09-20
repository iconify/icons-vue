<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg00t0bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xg00t0bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:plus" /></template>
