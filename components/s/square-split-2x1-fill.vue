<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbhvcjbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qbhvcjbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-split-2x1-fill" /></template>
