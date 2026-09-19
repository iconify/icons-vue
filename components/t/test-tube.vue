<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu2u05fim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu2u05fim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:test-tube" /></template>
