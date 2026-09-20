<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-3uxnbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-3uxnbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:translate-line" /></template>
