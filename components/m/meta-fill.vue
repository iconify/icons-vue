<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/advjs7-_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="advjs7-_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:meta-fill" /></template>
