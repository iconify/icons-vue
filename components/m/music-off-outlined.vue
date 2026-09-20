<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3pk9cb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3pk9cb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:music-off-outlined" /></template>
