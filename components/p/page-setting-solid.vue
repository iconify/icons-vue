<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0uo5wbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e0uo5wbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:page-setting-solid" /></template>
