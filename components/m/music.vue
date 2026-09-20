<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgi23wtae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgi23wtae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:music" /></template>
