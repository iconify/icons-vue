<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy2evxbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sy2evxbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:repeat-single-solid" /></template>
