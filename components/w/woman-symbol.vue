<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxa_mgbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zxa_mgbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:woman-symbol" /></template>
