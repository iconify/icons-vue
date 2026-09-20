<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jifwxdexe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jifwxdexe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:steps-2-solid" /></template>
