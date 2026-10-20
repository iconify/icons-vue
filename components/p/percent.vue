<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po_r04bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po_r04bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:percent" /></template>
