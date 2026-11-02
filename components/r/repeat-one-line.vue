<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nll8v2b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nll8v2b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:repeat-one-line" /></template>
