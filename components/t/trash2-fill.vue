<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o72q58bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o72q58bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:trash2-fill" /></template>
