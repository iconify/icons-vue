<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjr4ghz5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjr4ghz5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:moodle" /></template>
