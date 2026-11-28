<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akaspub_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akaspub_j primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parenthesis-right-duotone" /></template>
