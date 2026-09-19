<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih6dy_bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih6dy_bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:xiaomi-p70" /></template>
