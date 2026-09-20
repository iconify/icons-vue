<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7ck9ukgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e7ck9ukgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:stairs-1-solid" /></template>
