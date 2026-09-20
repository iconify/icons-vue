<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soznfibkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soznfibkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:volume-off-vibrate-fill" /></template>
