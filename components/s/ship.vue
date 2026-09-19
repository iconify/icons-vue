<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5fc0wbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f5fc0wbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:ship" /></template>
