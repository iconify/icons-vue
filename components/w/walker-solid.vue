<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lczuqebok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lczuqebok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:walker-solid" /></template>
