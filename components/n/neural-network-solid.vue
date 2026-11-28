<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_n0vpbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_n0vpbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:neural-network-solid" /></template>
