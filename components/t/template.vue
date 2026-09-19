<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk52cbcqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk52cbcqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:template" /></template>
