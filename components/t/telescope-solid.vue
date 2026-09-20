<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pllcr1bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pllcr1bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:telescope-solid" /></template>
