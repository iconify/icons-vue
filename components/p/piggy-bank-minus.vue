<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb0_6tbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb0_6tbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:piggy-bank-minus" /></template>
