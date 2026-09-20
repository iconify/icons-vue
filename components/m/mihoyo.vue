<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5v31ibvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5v31ibvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mihoyo" /></template>
