<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o52-yzblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o52-yzblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:subject" /></template>
