<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4ggub3vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="a4ggub3vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:next" /></template>
