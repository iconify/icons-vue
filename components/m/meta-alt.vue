<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr74ui3xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr74ui3xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:meta-alt" /></template>
