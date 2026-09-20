<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s137axaes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s137axaes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:stencyl" /></template>
