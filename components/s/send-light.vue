<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgcsv3b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgcsv3b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:send-light" /></template>
