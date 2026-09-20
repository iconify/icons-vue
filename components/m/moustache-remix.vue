<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j37p8-b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j37p8-b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:moustache-remix" /></template>
