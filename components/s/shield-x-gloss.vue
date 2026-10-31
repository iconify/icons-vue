<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd6bibcxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd6bibcxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-x-gloss" /></template>
