<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e442e8d9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e442e8d9k primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-3-duotone" /></template>
