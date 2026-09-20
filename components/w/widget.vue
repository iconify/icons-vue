<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbnt92bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vbnt92bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:widget" /></template>
