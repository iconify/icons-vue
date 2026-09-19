<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7cu91b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u7cu91b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-circle-fill" /></template>
