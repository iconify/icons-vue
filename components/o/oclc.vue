<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg0-37bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg0-37bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:oclc" /></template>
