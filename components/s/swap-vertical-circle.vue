<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqjd73bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqjd73bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:swap-vertical-circle" /></template>
