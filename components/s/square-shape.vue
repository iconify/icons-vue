<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srkozk11h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="srkozk11h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:square-shape" /></template>
