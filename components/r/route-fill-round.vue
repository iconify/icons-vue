<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkq05rbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkq05rbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route-fill-round" /></template>
