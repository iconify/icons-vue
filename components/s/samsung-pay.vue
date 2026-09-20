<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4lg_7bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4lg_7bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:samsung-pay" /></template>
