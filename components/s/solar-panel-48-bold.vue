<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v21_iw5xw.css';
import '../../css/u/ul5y7nsoe.css';
import '../../css/v/vb74a5b1y.css';
import '../../css/i/i73i1vb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v21_iw5xw"/><path class="ul5y7nsoe"/><path class="vb74a5b1y"/><path class="i73i1vb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-panel-48-bold" /></template>
