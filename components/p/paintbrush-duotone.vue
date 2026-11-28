<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yydu7fitl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary yydu7fitl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:paintbrush-duotone" /></template>
