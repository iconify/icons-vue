<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsxx68wym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsxx68wym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:pen" /></template>
