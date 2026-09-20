<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcq_hib2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jcq_hib2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ok-hand-remix" /></template>
