<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avn7-_bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avn7-_bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:radio-off" /></template>
