<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwhra4biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qwhra4biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wine-bottle-and-wine-glass" /></template>
