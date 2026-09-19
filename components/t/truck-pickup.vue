<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbvjn4b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="xbvjn4b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:truck-pickup" /></template>
