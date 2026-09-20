<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_1_4bc4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d_1_4bc4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:projector-screen-solid" /></template>
