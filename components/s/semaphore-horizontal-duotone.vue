<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gehfu_7md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gehfu_7md primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:semaphore-horizontal-duotone" /></template>
