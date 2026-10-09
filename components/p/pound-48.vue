<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncqap6kqt.css';
import '../../css/w/w4cmqe7qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ncqap6kqt"/><path class="w4cmqe7qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pound-48" /></template>
