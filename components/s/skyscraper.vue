<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saf6hkt8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saf6hkt8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:skyscraper" /></template>
