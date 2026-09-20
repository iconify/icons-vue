<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo5b263yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vo5b263yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:triangle-arrow-expand-remix" /></template>
