<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hivm86b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="hivm86b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:reddit" /></template>
