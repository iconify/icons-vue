<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddwzp2bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddwzp2bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:xilinx" /></template>
