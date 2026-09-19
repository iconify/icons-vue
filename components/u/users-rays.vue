<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az9e_ccag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="az9e_ccag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:users-rays" /></template>
