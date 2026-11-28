<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj07_abtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj07_abtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rss-solid" /></template>
