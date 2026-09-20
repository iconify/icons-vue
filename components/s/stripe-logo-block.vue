<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg2ybx44l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pg2ybx44l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:stripe-logo-block" /></template>
