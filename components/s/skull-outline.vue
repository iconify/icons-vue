<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8-qn0b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t8-qn0b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:skull-outline" /></template>
