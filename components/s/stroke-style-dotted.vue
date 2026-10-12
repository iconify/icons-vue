<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbwpj6mtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbwpj6mtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:stroke-style-dotted" /></template>
