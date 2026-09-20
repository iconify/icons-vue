<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaedl0tuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaedl0tuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:puppet" /></template>
