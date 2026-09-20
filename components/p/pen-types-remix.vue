<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv55i0bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv55i0bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pen-types-remix" /></template>
