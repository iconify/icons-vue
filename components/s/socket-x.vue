<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm_lp0ajf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm_lp0ajf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:socket-x" /></template>
