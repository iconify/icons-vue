<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp2jyjjny.css';
import '../../css/t/t4ppgnbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jp2jyjjny"/><path class="t4ppgnbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:temperature" /></template>
