<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqcijfbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pqcijfbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:new-file-remix" /></template>
