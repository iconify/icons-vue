<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3fbu37eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3fbu37eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-cells-split-outline" /></template>
