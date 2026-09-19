<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2lsc3b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2lsc3b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-pause-bold" /></template>
