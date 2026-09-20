<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xism68mgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xism68mgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mingww64" /></template>
