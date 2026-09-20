<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/holfdgb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="holfdgb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:radar-2-filled" /></template>
