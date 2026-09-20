<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_v2-7tnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t_v2-7tnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shopping-basket-2-remix" /></template>
