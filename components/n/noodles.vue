<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1guqcscz.css';
import '../../css/o/ontwibcre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o1guqcscz"/><path class="ontwibcre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconito:noodles" /></template>
