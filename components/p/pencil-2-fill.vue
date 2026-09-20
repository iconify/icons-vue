<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aib1ujbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aib1ujbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-2-fill" /></template>
