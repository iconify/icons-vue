<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akqvb5brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akqvb5brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:playground-slide" /></template>
