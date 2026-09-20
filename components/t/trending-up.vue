<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj5w7lbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj5w7lbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:trending-up" /></template>
