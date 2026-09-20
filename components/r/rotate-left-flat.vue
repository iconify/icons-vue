<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csx3unbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="csx3unbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:rotate-left-flat" /></template>
