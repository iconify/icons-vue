<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtdzw85ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtdzw85ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:teddy-bear-outline" /></template>
