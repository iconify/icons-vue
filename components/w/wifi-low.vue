<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkkbbgben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkkbbgben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wifi-low" /></template>
