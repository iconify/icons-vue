<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrq-4jbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="zrq-4jbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:rail-11" /></template>
