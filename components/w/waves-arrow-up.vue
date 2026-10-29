<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhu5zrben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhu5zrben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:waves-arrow-up" /></template>
