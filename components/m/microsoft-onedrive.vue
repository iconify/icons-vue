<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfhd1vbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfhd1vbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-onedrive" /></template>
