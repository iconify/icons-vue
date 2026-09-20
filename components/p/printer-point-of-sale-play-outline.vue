<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsa0oe37a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsa0oe37a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-play-outline" /></template>
