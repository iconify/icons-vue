<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sft1b-ftv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sft1b-ftv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:minus" /></template>
