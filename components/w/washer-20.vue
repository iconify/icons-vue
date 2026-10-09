<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thq_bacgc.css';
import '../../css/n/njhh4kbbo.css';
import '../../css/z/za8ynewwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="thq_bacgc"/><path class="njhh4kbbo"/><path class="za8ynewwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:washer-20" /></template>
