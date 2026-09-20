<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijgrgobum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijgrgobum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:suitcase-line" /></template>
