<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv4kqfbhb.css';
import '../../css/k/kqk5arb5g.css';
import '../../css/l/lpcx7nb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zv4kqfbhb"/><path class="kqk5arb5g"/><path class="lpcx7nb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tidal-lagoon-48" /></template>
