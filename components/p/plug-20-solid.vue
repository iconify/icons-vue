<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h21mulwpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h21mulwpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:plug-20-solid" /></template>
