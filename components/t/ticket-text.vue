<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sof9ji8mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sof9ji8mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:ticket-text" /></template>
