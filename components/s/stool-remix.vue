<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na_s0_b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="na_s0_b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:stool-remix" /></template>
