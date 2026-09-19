<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcc-o1b9v.css';
import '../../css/d/d6vy5dbmt.css';
import '../../css/y/yqdcx39ai.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 qcc-o1b9v"/><path class="clr-i-outline clr-i-outline-path-2 d6vy5dbmt"/><path class="clr-i-outline clr-i-outline-path-3 yqdcx39ai"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:printer-line" /></template>
