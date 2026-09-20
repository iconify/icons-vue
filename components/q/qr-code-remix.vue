<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaa-b8puh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oaa-b8puh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:qr-code-remix" /></template>
