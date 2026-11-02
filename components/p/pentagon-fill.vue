<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex-8-wbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex-8-wbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pentagon-fill" /></template>
