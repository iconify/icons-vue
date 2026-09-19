<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg4mjnb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg4mjnb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:rotate-right" /></template>
