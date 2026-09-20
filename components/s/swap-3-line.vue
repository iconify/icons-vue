<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehzb5827t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehzb5827t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:swap-3-line" /></template>
