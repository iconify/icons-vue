<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh45k69ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh45k69ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:remove-favorite-highlight" /></template>
