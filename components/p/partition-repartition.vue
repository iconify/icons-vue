<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1dhfvbmz.css';
import '../../css/c/cymo4yqyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k1dhfvbmz"/><path class="cymo4yqyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:partition-repartition" /></template>
