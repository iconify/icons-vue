<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aajqmxblx.css';
import '../../css/l/lt_twkb4l.css';
import '../../css/p/p78aomkxz.css';
import '../../css/s/s0y6ktbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aajqmxblx"/><path class="lt_twkb4l"/><path class="p78aomkxz"/><path class="s0y6ktbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shed-20" /></template>
