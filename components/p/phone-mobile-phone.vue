<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9ep4jbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="o9ep4jbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:phone-mobile-phone" /></template>
