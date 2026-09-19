<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7e4c-bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7e4c-bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roomsmancave" /></template>
