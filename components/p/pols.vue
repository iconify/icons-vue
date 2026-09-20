<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzls2o0vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wzls2o0vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pols" /></template>
