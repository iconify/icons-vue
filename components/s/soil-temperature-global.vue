<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5ewtco_s.css';
import '../../css/v/vpg-ykb3g.css';
import '../../css/a/axl75o_4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q5ewtco_s"/><path class="vpg-ykb3g"/><path class="axl75o_4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:soil-temperature-global" /></template>
