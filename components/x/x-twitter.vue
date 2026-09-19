<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6_jc6bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q6_jc6bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:x-twitter" /></template>
