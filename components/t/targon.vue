<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgx5q2o1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="tgx5q2o1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:targon" /></template>
