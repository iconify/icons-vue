<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-294_b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l-294_b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:paste" /></template>
