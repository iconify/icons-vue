<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de9ov5bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="de9ov5bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:stock-solid" /></template>
