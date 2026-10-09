<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qebrtob4g.css';
import '../../css/e/exrhjpbkr.css';
import '../../css/s/skd1_2bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qebrtob4g"/><path class="exrhjpbkr"/><path class="skd1_2bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:washer-20-bold" /></template>
