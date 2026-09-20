<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni37043rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni37043rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:textalign-right-filled" /></template>
