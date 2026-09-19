<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3u0_wbck.css';
import '../../css/y/yalmj9bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3u0_wbck"/><path class="yalmj9bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:speaker" /></template>
