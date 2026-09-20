<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ticadcbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ticadcbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-1-fill" /></template>
