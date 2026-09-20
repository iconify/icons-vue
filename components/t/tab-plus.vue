<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlemv9bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlemv9bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:tab-plus" /></template>
