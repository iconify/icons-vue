<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnrdxabwp.css';
import '../../css/v/vbp1sgblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="hnrdxabwp"/><path clip-rule="evenodd" class="vbp1sgblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nixos" /></template>
