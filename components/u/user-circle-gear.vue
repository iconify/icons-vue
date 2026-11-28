<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cai6_4o_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cai6_4o_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-circle-gear" /></template>
