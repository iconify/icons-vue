<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj4366b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hj4366b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:sticky" /></template>
