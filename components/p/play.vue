<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo6xumbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1600};
const content = `<path class="fo6xumbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:play" /></template>
