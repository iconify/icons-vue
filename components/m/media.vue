<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c76_bpbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c76_bpbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:media" /></template>
