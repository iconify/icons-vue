<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gna5_sg5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gna5_sg5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whitelatincross" /></template>
