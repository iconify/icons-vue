<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf351fbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf351fbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wifi-1" /></template>
