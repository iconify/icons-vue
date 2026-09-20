<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilmv3rwlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ilmv3rwlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:sun-solid" /></template>
