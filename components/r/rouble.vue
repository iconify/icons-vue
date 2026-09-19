<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfqf04b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1408};
const content = `<path class="sfqf04b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:rouble" /></template>
