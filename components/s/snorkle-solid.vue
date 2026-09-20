<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4qkq3-ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d4qkq3-ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:snorkle-solid" /></template>
