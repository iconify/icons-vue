<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d92pih7bm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d92pih7bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-30-fill" /></template>
