<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs2p5x73g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs2p5x73g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:preact" /></template>
