<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhgab4ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":832,"height":1600};
const content = `<path class="qhgab4ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:star-half" /></template>
