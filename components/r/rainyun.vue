<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts2d2vjbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts2d2vjbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rainyun" /></template>
