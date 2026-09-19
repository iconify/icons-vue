<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgm--ccyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgm--ccyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:triangle-filled" /></template>
