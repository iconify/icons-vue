<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if1i_5bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="if1i_5bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:receipt-remix" /></template>
