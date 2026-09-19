<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-yo_-0xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-yo_-0xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:snowflake-filled" /></template>
