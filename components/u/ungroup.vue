<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mppp2xb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mppp2xb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ungroup" /></template>
