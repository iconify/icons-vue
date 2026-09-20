<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1sgngb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1sgngb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:moon-waxing-gibbous" /></template>
