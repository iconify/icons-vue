<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5q7mwbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k5q7mwbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:question-filled" /></template>
