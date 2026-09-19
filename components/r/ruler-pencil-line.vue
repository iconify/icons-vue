<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9zjpsbxq.css';
import '../../css/i/izomx4vfd.css';
import '../../css/r/rra0q9q9g.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 d9zjpsbxq"/><path class="clr-i-outline clr-i-outline-path-2 izomx4vfd"/><path class="clr-i-outline clr-i-outline-path-3 rra0q9q9g"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:ruler-pencil-line" /></template>
