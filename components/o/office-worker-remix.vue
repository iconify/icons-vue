<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwynthbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uwynthbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:office-worker-remix" /></template>
