<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zogy43b-o.css';
import '../../css/v/vn8q6zg-o.css';
import '../../css/q/q4lpfqb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zogy43b-o"/><path class="vn8q6zg-o"/><path class="q4lpfqb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rugby-20" /></template>
