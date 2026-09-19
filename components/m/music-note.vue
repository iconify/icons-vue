<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk72dvbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk72dvbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:music-note" /></template>
