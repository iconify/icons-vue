<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzycj6brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzycj6brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wifi-off" /></template>
