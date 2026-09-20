<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1e2dfvwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1e2dfvwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:pen-solid" /></template>
