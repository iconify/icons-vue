<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y10l5hgkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y10l5hgkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-plus-square-thin" /></template>
