<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zroepubiq.css';
import '../../css/z/z-9b709tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zroepubiq"/><path class="z-9b709tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:packer" /></template>
