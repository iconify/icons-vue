<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9a7r7b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x9a7r7b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:quotation-2-solid" /></template>
