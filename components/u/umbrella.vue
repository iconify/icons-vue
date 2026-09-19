<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix_ay1bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ix_ay1bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:umbrella" /></template>
