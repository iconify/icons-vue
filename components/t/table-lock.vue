<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy3uh_bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy3uh_bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-lock" /></template>
