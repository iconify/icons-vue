<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8t1-_2-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y8t1-_2-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:snowflake-bold" /></template>
