<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-lzg5sjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o-lzg5sjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:text" /></template>
