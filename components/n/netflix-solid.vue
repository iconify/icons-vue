<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra_3kbbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ra_3kbbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:netflix-solid" /></template>
