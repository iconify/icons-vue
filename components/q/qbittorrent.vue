<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du-gkabvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du-gkabvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:qbittorrent" /></template>
