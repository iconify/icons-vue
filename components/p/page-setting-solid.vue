<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgs7_jqez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lgs7_jqez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:page-setting-solid" /></template>
