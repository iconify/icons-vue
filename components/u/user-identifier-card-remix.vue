<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfc1qmbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wfc1qmbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:user-identifier-card-remix" /></template>
