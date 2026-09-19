<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3dvt7jpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q3dvt7jpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:picasa" /></template>
