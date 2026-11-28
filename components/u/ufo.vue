<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuut-rowa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuut-rowa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ufo" /></template>
