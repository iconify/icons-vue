<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhoo-skte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhoo-skte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wifi-line" /></template>
