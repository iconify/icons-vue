<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygyd9kulc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="ygyd9kulc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:underline" /></template>
