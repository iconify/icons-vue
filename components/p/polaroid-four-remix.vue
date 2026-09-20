<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr0t-cb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pr0t-cb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:polaroid-four-remix" /></template>
