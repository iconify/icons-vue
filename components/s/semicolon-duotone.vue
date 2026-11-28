<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oche6t6ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oche6t6ju primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:semicolon-duotone" /></template>
