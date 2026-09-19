<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qibh9ubbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qibh9ubbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:snowflake-alt" /></template>
