<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukjsobcvo.css';
import '../../css/v/vss9bg_wd.css';
import '../../css/c/cndhhqb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ukjsobcvo"/><path class="vss9bg_wd"/><path class="cndhhqb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:windmill-20" /></template>
