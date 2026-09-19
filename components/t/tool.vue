<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j27f_maji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j27f_maji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:tool" /></template>
