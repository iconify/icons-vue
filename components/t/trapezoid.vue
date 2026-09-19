<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw0wsk98j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tw0wsk98j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:trapezoid" /></template>
