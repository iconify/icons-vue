<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or9v270tb.css';
import '../../css/s/ssto5nbhy.css';
import '../../css/i/i-7yv1x4c.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--alerted clr-i-outline-path-1--alerted or9v270tb"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted ssto5nbhy"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted i-7yv1x4c"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-4--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tasks-outline-alerted" /></template>
