<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbajddz8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbajddz8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-cells-large-filled" /></template>
