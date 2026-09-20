<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-e96896z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x-e96896z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sort-descending-remix" /></template>
