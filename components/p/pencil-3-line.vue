<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/allvd7xat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="allvd7xat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-3-line" /></template>
