<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q494w3bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q494w3bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tree-heart" /></template>
