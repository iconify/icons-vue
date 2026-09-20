<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxlnc7bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxlnc7bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panorama-outline" /></template>
