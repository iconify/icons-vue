<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzn6d_bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzn6d_bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:parasol" /></template>
