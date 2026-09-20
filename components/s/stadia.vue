<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq96s7b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq96s7b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:stadia" /></template>
