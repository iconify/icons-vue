<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_3ltgb8o.css';
import '../../css/o/o9p1ubbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s_3ltgb8o"/><path class="o9p1ubbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:vending-hot-drink2" /></template>
