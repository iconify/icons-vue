<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iig1kgbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iig1kgbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:octagram-edit-outline" /></template>
