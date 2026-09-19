<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps21uubtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ps21uubtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:psychology2x-outline" /></template>
