<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk71f6p-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk71f6p-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:notification-outline-plus" /></template>
