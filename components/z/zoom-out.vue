<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abtp8tbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abtp8tbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:zoom-out" /></template>
