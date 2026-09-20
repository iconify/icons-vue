<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojwgjs_ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojwgjs_ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:volume" /></template>
