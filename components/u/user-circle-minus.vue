<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k19r2xnlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k19r2xnlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-circle-minus" /></template>
