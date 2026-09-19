<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqi-weisu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":384};
const content = `<path class="uqi-weisu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:play" /></template>
