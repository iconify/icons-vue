<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orre3bifv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="orre3bifv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:peace-symbol-flat" /></template>
