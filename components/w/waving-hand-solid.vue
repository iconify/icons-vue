<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5a3ny35e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d5a3ny35e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:waving-hand-solid" /></template>
