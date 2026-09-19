<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj8g_sb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj8g_sb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:remote" /></template>
