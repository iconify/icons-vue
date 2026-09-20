<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4og9jlue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k4og9jlue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-cute-remix" /></template>
