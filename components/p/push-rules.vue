<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir-wcidyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ir-wcidyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:push-rules" /></template>
