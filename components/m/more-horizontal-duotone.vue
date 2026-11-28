<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp294gxeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp294gxeo primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:more-horizontal-duotone" /></template>
