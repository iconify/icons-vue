<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhczfhb2e.css';
import '../../css/c/clf6f0bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lhczfhb2e"/><path class="clf6f0bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trending-down-20" /></template>
