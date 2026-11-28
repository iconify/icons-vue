<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oze_5-bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oze_5-bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:taxi" /></template>
