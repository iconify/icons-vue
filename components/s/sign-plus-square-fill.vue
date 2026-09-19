<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q11hb9bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q11hb9bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-square-fill" /></template>
