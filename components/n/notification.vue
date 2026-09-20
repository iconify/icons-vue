<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmf-0pbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmf-0pbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:notification" /></template>
