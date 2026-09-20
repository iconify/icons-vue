<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxmu_kblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wxmu_kblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:music-filled" /></template>
