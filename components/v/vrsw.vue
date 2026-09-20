<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw2nn3blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw2nn3blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vrsw" /></template>
