<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce1150bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":78,"height":26};
const content = `<path class="ce1150bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-bold-support-26" /></template>
