<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vv3m6lbyb.css';
import '../../css/r/r9eucsbka.css';
import '../../css/v/v6xozwwqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vv3m6lbyb"/><path class="r9eucsbka"/><path class="v6xozwwqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-square-3-broken" /></template>
