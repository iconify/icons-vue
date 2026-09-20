<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjgcf6wck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjgcf6wck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mercado-pago" /></template>
