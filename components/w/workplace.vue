<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onfay2_lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onfay2_lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:workplace" /></template>
