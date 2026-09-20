<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngfh1_bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngfh1_bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-heart" /></template>
