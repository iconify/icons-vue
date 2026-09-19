<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj3vvdbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="wj3vvdbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:vr-cardboard" /></template>
