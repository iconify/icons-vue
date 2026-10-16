<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcea63bav.css';
import '../../css/r/rtjb2ejcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fcea63bav"/><path class="rtjb2ejcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phase-shifter-20-bold" /></template>
