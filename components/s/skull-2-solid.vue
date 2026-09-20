<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqcaekbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zqcaekbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:skull-2-solid" /></template>
