<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkap0cz0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mkap0cz0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:svg" /></template>
