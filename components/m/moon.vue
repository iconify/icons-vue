<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4gzb_bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4gzb_bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:moon" /></template>
