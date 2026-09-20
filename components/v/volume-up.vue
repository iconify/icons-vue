<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti7n7f08l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ti7n7f08l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:volume-up" /></template>
