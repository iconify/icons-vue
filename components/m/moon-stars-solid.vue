<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbsbh4bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nbsbh4bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:moon-stars-solid" /></template>
