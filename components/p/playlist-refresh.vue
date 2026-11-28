<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc1rpebar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc1rpebar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:playlist-refresh" /></template>
