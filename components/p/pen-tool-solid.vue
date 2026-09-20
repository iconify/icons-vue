<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1x2ahbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e1x2ahbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pen-tool-solid" /></template>
