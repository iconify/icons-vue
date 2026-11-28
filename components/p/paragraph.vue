<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w848w8bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w848w8bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:paragraph" /></template>
