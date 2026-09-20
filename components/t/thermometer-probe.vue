<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlk0loasq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlk0loasq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:thermometer-probe" /></template>
