<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntlnahbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ntlnahbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:octagram-shape" /></template>
