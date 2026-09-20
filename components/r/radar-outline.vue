<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_de2x4vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_de2x4vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:radar-outline" /></template>
