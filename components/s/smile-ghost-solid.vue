<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prstx4uvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prstx4uvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:smile-ghost-solid" /></template>
