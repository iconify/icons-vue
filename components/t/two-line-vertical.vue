<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwmxn8bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwmxn8bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:two-line-vertical" /></template>
