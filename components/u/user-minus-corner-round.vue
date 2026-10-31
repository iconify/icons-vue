<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv5_w2gaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv5_w2gaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-minus-corner-round" /></template>
