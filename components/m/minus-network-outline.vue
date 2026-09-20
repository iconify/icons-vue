<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra3wu2bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra3wu2bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:minus-network-outline" /></template>
