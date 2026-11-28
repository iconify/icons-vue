<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5dfn_bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5dfn_bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:phone-call-x" /></template>
