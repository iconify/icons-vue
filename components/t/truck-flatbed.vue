<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhnm5fbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhnm5fbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-flatbed" /></template>
