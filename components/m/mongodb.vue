<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgkhlxbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="xgkhlxbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:mongodb" /></template>
