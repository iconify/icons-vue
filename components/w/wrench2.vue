<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avsd8cb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="avsd8cb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:wrench2" /></template>
