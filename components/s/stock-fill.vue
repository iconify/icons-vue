<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thbkw0bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thbkw0bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stock-fill" /></template>
