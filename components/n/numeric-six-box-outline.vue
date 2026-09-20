<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8plzgb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8plzgb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-six-box-outline" /></template>
