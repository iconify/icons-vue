<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4evi6bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l4evi6bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:wallet-remix" /></template>
