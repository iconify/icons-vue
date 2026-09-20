<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu_n6gdgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hu_n6gdgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:qr-code-remix" /></template>
