<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i82l_mncq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i82l_mncq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thumb-up-2-line" /></template>
