<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx2prybdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx2prybdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:spirals" /></template>
