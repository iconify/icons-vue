<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxe8n-bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sxe8n-bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:saxophone-16" /></template>
