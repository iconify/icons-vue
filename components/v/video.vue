<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffjlyobju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffjlyobju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:video" /></template>
