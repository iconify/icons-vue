<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx1swlb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx1swlb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shorter-ai" /></template>
