<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vevl8ac-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vevl8ac-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-factorial-fill" /></template>
