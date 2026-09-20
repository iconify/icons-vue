<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1mg6obnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1mg6obnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:myget" /></template>
