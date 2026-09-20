<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6g2eix9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6g2eix9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt2" /></template>
