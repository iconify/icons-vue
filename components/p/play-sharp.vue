<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw432ybht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lw432ybht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:play-sharp" /></template>
