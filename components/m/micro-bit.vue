<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehcfzl_ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehcfzl_ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:micro-bit" /></template>
