<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2121-bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2121-bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:radio-tower-solid" /></template>
