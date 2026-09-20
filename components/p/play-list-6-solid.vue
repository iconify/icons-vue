<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e31b-bcfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e31b-bcfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:play-list-6-solid" /></template>
