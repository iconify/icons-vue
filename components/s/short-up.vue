<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t436v9fxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t436v9fxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:short-up" /></template>
