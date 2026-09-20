<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmxa0tngr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmxa0tngr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:shi" /></template>
