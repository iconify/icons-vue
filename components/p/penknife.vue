<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhxywsbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="jhxywsbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:penknife" /></template>
