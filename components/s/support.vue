<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b45pj9bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b45pj9bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:support" /></template>
