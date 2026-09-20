<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvj4ouunw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cvj4ouunw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:printer-remix" /></template>
