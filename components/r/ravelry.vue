<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv0z-vbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv0z-vbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ravelry" /></template>
