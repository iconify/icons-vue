<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4zgpzbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j4zgpzbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:spike-strip" /></template>
