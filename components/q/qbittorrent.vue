<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cej_izyna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cej_izyna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:qbittorrent" /></template>
