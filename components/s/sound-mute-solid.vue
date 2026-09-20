<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo-hi3hch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo-hi3hch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:sound-mute-solid" /></template>
