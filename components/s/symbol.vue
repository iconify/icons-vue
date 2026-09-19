<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cakg9fd0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cakg9fd0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:symbol" /></template>
