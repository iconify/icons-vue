<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chkt45bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chkt45bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shield-half" /></template>
