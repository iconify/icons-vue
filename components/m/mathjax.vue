<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0fd-kbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="s0fd-kbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:mathjax" /></template>
