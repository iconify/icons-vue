<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axz7gbckk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axz7gbckk primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:maximize-duotone" /></template>
