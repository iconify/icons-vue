<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxlhkovva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nxlhkovva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:table-cells-split-solid" /></template>
