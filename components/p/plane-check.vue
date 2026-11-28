<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv42hnbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv42hnbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:plane-check" /></template>
