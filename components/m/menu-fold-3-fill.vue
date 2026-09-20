<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1kketwvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1kketwvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-fold-3-fill" /></template>
