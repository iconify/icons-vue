<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm5up5pot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm5up5pot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sleigh-fill" /></template>
