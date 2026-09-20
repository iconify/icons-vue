<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huregbpym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huregbpym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:slnd" /></template>
