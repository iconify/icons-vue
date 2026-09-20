<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa8hrrbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa8hrrbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:next-fill" /></template>
