<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8g73tbef.css';
import '../../css/k/kui6b9bke.css';
import '../../css/y/yzh_ltb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u8g73tbef"/><path class="kui6b9bke"/><path class="yzh_ltb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tape-measure-48-bold" /></template>
