<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfgbbrboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfgbbrboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:newspaper" /></template>
