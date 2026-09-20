<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfz7s0qpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yfz7s0qpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:monitor-o" /></template>
