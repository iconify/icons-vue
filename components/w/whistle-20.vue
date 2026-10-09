<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-mqzbcjv.css';
import '../../css/s/s1s3q_bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f-mqzbcjv"/><path class="s1s3q_bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whistle-20" /></template>
