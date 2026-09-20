<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t22_x14sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t22_x14sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sage" /></template>
