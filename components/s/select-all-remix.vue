<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_f_i1b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j_f_i1b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:select-all-remix" /></template>
