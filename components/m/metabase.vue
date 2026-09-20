<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsh0a7b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsh0a7b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:metabase" /></template>
