<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9k00b_1r.css';
import '../../css/w/wr4tv666r.css';
import '../../css/f/faz73x6ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u9k00b_1r"/><path class="wr4tv666r"/><path class="faz73x6ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:yen-20" /></template>
