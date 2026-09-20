<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrbquor0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrbquor0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-seven-circle-outline" /></template>
