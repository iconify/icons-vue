<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-n7qqbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-n7qqbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:spotlight" /></template>
