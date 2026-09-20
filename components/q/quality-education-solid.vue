<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kglg-tb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kglg-tb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:quality-education-solid" /></template>
