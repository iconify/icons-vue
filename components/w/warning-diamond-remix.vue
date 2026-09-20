<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n65bkfbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n65bkfbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:warning-diamond-remix" /></template>
