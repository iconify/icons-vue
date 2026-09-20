<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp2fribyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rp2fribyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:street-sign-solid" /></template>
