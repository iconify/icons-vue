<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1yu42i0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o1yu42i0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:scanner-bar-code-solid" /></template>
