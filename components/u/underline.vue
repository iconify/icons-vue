<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox1-hbb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox1-hbb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:underline" /></template>
