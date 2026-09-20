<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-hww2b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-hww2b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:pen" /></template>
