<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbk2lq5ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":504};
const content = `<path class="wbk2lq5ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:quora" /></template>
