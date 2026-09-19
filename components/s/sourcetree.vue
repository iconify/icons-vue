<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efihy-46x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efihy-46x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:sourcetree" /></template>
