<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trrtt2yqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="trrtt2yqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:radioactive-1" /></template>
