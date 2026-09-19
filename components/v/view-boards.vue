<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1wtx_blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1wtx_blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:view-boards" /></template>
