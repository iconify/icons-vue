<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9gnjlb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9gnjlb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:order-bool-descending-variant" /></template>
