<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8nn4p3qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j8nn4p3qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:plus" /></template>
