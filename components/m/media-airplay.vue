<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cemc4ji5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cemc4ji5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-airplay" /></template>
