<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx8adxb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1984,"height":1792};
const content = `<path class="xx8adxb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pied-piper-alt" /></template>
