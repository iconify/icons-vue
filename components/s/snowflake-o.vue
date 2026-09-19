<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0_9m3btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1600,"height":1792};
const content = `<path class="s0_9m3btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:snowflake-o" /></template>
