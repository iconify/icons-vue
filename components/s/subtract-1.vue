<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n34sis0pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="n34sis0pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:subtract-1" /></template>
