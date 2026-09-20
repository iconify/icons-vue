<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5mc0u7xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5mc0u7xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:undo-variant" /></template>
