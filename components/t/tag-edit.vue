<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3b3-73sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3b3-73sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-edit" /></template>
