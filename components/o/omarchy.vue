<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt3t3qzmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt3t3qzmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:omarchy" /></template>
