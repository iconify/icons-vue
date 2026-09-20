<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-5hvoban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d-5hvoban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:production-belt-remix" /></template>
