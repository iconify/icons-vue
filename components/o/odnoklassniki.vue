<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z55t-is9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z55t-is9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:odnoklassniki" /></template>
