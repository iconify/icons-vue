<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhdhe4-ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hhdhe4-ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:smog" /></template>
