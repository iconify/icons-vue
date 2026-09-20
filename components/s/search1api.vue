<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij6y9bwyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ij6y9bwyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:search1api" /></template>
