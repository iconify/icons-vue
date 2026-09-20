<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m89ik2bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m89ik2bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sound-quiet" /></template>
