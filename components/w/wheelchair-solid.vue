<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa620dg4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xa620dg4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:wheelchair-solid" /></template>
