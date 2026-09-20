<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x30kqj6eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x30kqj6eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:snow-flake-flat" /></template>
