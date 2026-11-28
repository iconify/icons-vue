<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta6s0kbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ta6s0kbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-slash-bold" /></template>
