<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvca9t96l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvca9t96l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:quote-alt-left" /></template>
