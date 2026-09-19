<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5dtazbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x5dtazbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:peseta-sign" /></template>
