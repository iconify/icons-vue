<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noiv9eb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="noiv9eb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:parliament-solid" /></template>
