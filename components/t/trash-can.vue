<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_kz3cc2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q_kz3cc2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:trash-can" /></template>
