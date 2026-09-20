<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecto0z3-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecto0z3-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevrons-left-fill" /></template>
