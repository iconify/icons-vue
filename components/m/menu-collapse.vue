<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugg_ysbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugg_ysbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:menu-collapse" /></template>
