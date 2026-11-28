<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw189cc1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw189cc1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:server-solid" /></template>
