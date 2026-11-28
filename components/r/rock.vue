<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs3j8ab6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs3j8ab6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:rock" /></template>
