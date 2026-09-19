<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh-t7_bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wh-t7_bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:triangle-up-12" /></template>
