<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hspnghblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hspnghblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whitemediumsquare" /></template>
