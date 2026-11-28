<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jojxz6b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jojxz6b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:train-check" /></template>
