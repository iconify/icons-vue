<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy3fjbcsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy3fjbcsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:wheelchair-basketball" /></template>
