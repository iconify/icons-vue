<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta9oaqh9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta9oaqh9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:monitor" /></template>
