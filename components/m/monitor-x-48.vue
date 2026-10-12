<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9mi-m0jn.css';
import '../../css/a/azjk1obih.css';
import '../../css/k/kng-rnbst.css';
import '../../css/b/bdkl8-dne.css';
import '../../css/j/j3cy-fbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a9mi-m0jn"/><path class="azjk1obih"/><path class="kng-rnbst"/><path class="bdkl8-dne"/><path class="j3cy-fbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monitor-x-48" /></template>
