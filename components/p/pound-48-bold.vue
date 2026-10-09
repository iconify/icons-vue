<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_2pqsbdw.css';
import '../../css/e/et2f85cnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_2pqsbdw"/><path class="et2f85cnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pound-48-bold" /></template>
