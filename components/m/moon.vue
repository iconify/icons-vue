<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otch78b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="otch78b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:moon" /></template>
