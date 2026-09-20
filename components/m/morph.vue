<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz1c8bb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz1c8bb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:morph" /></template>
