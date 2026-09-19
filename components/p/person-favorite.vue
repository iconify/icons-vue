<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjn4zlb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rjn4zlb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:person-favorite" /></template>
