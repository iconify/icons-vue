<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bopqqgw4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bopqqgw4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:razor-single-edge" /></template>
