<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un00tbbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un00tbbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zeta-chain" /></template>
