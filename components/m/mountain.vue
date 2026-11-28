<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkk3kgb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkk3kgb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mountain" /></template>
