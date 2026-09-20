<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3n9mrxup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3n9mrxup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:night-club-disco-ball-1" /></template>
