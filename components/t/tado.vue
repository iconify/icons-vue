<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p72o0uxnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p72o0uxnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tado" /></template>
