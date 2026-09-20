<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7xvi4-_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a7xvi4-_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:todo-add" /></template>
