<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjxi_ac1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjxi_ac1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-lock-open" /></template>
