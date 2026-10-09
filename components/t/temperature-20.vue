<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il0bcibcq.css';
import '../../css/z/z8-myrbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="il0bcibcq"/><path class="z8-myrbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:temperature-20" /></template>
