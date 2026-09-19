<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dytf-3bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dytf-3bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-next" /></template>
