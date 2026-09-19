<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf4iksbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf4iksbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:timeline" /></template>
