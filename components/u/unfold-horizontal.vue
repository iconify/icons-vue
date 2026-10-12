<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8334x15o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8334x15o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:unfold-horizontal" /></template>
