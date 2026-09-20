<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwmncibou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iwmncibou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:module-puzzle-2" /></template>
