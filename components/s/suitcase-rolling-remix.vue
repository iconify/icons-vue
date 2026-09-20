<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr9kh0b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kr9kh0b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:suitcase-rolling-remix" /></template>
