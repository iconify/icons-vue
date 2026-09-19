<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f00c69yzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="f00c69yzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:opnsense-wordmark" /></template>
