<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8j-mf_mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z8j-mf_mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pixijs-wordmark" /></template>
