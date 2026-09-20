<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfc8g4bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfc8g4bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:settings-fill" /></template>
