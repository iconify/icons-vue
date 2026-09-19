<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uck3k8wiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uck3k8wiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:underline" /></template>
