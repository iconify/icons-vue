<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuhbexp4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nuhbexp4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:t-bubble-fill" /></template>
