<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8neiopvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8neiopvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:table-cells-split" /></template>
