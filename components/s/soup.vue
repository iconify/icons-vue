<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu4nmubmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu4nmubmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:soup" /></template>
