<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca2ckcfef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca2ckcfef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:soap-dispenser-droplet" /></template>
