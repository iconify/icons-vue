<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihjidgbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihjidgbvf primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-root-duotone" /></template>
