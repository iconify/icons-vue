<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqid-obeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nqid-obeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:renault" /></template>
