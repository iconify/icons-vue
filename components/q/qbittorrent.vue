<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5u0_fbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5u0_fbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:qbittorrent" /></template>
