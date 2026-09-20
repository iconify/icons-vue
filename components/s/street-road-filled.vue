<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbno5b9ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbno5b9ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:street-road-filled" /></template>
