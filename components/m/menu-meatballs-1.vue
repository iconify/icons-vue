<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozn0_bc3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="ozn0_bc3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:menu-meatballs-1" /></template>
