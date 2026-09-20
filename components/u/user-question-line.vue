<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kht5u-kyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kht5u-kyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-question-line" /></template>
