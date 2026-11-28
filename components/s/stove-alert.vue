<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjtvx7-gn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjtvx7-gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:stove-alert" /></template>
