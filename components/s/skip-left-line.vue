<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3ldsk1xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3ldsk1xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:skip-left-line" /></template>
