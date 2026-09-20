<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2x-_ybte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c2x-_ybte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:prescription-pills-drugs-healthcare-solid" /></template>
