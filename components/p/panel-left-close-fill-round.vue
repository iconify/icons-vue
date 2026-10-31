<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw_p5en_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw_p5en_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-left-close-fill-round" /></template>
