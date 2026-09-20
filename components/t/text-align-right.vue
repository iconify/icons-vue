<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf_byub7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf_byub7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:text-align-right" /></template>
