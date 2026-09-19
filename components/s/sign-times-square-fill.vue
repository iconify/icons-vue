<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0nbbgb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0nbbgb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-times-square-fill" /></template>
