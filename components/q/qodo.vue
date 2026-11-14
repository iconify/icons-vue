<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my18y5bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="my18y5bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:qodo" /></template>
