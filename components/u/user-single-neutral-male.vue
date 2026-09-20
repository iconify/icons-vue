<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l---ccb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l---ccb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-single-neutral-male" /></template>
