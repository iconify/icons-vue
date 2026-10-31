<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksd246hoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksd246hoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toggle-left-round" /></template>
