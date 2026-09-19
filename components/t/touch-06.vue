<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s093hob-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s093hob-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:touch-06" /></template>
