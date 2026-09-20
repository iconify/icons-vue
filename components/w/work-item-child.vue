<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmpkq65gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xmpkq65gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:work-item-child" /></template>
