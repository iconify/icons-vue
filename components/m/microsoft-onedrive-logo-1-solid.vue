<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n04ma3bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n04ma3bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-onedrive-logo-1-solid" /></template>
