<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo_y6ybav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xo_y6ybav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:today-fill" /></template>
