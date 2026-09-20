<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjj9gwb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cjj9gwb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:page-setting-solid" /></template>
