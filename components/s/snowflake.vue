<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv0885bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yv0885bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:snowflake" /></template>
