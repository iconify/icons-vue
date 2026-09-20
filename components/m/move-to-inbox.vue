<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmdaz5j3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmdaz5j3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:move-to-inbox" /></template>
