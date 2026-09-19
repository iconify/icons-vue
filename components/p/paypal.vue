<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2dg93b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v2dg93b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:paypal" /></template>
