<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0n8p_5eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z0n8p_5eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pen-tool-solid" /></template>
