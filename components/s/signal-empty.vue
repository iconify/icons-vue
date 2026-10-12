<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fip2h6bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fip2h6bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:signal-empty" /></template>
