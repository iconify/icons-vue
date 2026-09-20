<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac7e6ph4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ac7e6ph4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:manual-book-remix" /></template>
