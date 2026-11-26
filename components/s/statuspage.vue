<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frv2dt3zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="frv2dt3zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:statuspage" /></template>
