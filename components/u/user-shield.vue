<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiexoyv5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jiexoyv5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:user-shield" /></template>
