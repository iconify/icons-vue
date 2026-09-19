<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eufkxlbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="eufkxlbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:updown-circle" /></template>
