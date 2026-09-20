<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwe524shh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwe524shh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wallet-plus-outline" /></template>
