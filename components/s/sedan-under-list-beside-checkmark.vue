<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeny3cb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aeny3cb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sedan-under-list-beside-checkmark" /></template>
