<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7z_9_tlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7z_9_tlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:plugins" /></template>
