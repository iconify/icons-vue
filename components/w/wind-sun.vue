<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpc1zdbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpc1zdbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:wind-sun" /></template>
