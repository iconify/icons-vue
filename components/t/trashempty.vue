<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmbrtgb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="tmbrtgb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:trashempty" /></template>
