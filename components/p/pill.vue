<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxf3oibnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cxf3oibnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:pill" /></template>
