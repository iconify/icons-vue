<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as-k-quki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as-k-quki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:size-small" /></template>
