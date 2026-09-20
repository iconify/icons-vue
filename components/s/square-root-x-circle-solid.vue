<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-w-62byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v-w-62byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:square-root-x-circle-solid" /></template>
