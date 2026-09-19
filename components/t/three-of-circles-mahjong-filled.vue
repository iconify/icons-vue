<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiip_5bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="aiip_5bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:three-of-circles-mahjong-filled" /></template>
