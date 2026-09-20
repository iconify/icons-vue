<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjsr8gbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jjsr8gbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:threat-phone-solid" /></template>
