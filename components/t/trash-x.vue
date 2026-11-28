<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7jpn2bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7jpn2bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:trash-x" /></template>
