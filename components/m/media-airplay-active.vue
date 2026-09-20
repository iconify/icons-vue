<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzio_6m8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzio_6m8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-airplay-active" /></template>
