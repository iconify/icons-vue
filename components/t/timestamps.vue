<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t604nob3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t604nob3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:timestamps" /></template>
