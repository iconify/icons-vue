<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcu6sacby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcu6sacby primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-0-duotone" /></template>
