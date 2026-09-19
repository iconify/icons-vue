<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6o_fdcnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6o_fdcnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-division-slash-light" /></template>
