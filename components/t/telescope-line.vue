<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maymkrsfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maymkrsfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:telescope-line" /></template>
