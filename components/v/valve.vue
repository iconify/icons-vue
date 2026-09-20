<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd31iab1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd31iab1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:valve" /></template>
