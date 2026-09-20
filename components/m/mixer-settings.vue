<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dktnxccgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dktnxccgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mixer-settings" /></template>
