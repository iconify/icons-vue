<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etb614apb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="etb614apb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:one-one" /></template>
