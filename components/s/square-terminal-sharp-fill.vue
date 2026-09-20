<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubh8lqqcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubh8lqqcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-terminal-sharp-fill" /></template>
