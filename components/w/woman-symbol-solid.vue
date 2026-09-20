<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5y1_cmmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z5y1_cmmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:woman-symbol-solid" /></template>
