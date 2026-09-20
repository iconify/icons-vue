<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr4dnob2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tr4dnob2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:medical-cross-sign-healthcare-flat" /></template>
