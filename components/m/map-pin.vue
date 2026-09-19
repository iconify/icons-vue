<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0lbkabqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":288,"height":512};
const content = `<path class="y0lbkabqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:map-pin" /></template>
