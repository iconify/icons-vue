<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y12ungb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y12ungb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:syringe" /></template>
