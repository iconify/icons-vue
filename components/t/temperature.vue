<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh3k1sbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh3k1sbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:temperature" /></template>
