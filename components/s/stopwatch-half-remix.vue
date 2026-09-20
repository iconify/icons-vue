<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abb0r2bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="abb0r2bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:stopwatch-half-remix" /></template>
