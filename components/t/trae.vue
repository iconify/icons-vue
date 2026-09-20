<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec9ix_0zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec9ix_0zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:trae" /></template>
