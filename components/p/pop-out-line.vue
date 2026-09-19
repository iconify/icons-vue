<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tji5q-s7d.css';
import '../../css/l/lv0bcs_yt.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 tji5q-s7d"/><path class="clr-i-outline clr-i-outline-path-2 lv0bcs_yt"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:pop-out-line" /></template>
