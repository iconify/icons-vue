<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiw_u92lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fiw_u92lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:skull-1-solid" /></template>
