<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy20y2b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy20y2b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-right-01" /></template>
