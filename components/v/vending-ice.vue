<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_3ltgb8o.css';
import '../../css/o/ojl0pt7uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s_3ltgb8o"/><path class="ojl0pt7uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:vending-ice" /></template>
