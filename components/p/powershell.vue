<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-xf7lbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="u-xf7lbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:powershell" /></template>
