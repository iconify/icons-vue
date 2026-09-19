<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnhzr4bxv.css';
import '../../css/v/va9ag7bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnhzr4bxv"/><path class="va9ag7bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:volume-up-outline" /></template>
