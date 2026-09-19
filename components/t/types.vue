<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um2e2-7hb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um2e2-7hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:types" /></template>
