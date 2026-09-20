<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrg32xrff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jrg32xrff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:radioactive-2-solid" /></template>
