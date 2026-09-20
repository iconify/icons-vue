<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6qrcobrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6qrcobrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-sort-horizontal-outline" /></template>
