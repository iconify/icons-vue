<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_dvk81hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_dvk81hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:music-3-fill" /></template>
