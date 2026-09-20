<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu2fvpofx.css';
import '../../css/b/bqv8f3bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bu2fvpofx"/><path clip-rule="evenodd" class="bqv8f3bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:task-16" /></template>
