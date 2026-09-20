<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rua772bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rua772bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-single-neutral-male-remix" /></template>
