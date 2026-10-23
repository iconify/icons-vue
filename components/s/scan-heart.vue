<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbv_wtb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbv_wtb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scan-heart" /></template>
