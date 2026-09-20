<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay24x4blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ay24x4blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mail-search-solid" /></template>
