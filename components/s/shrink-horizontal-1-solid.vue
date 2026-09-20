<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cevem_bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cevem_bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shrink-horizontal-1-solid" /></template>
