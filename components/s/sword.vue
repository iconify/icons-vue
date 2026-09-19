<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa_irwl6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pa_irwl6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sword" /></template>
