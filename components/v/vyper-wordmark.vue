<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idl-9rbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="idl-9rbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vyper-wordmark" /></template>
