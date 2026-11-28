<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkxm46j1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkxm46j1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-type-solid" /></template>
