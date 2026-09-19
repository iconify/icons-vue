<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn0076hxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn0076hxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-unite-filled" /></template>
