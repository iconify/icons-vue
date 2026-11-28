<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo4gjv_kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo4gjv_kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pill-x" /></template>
