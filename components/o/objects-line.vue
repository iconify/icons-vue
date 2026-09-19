<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4f47hb9w.css';
import '../../css/g/g2yqdbc5m.css';
import '../../css/v/vcbrqcbbw.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 v4f47hb9w"/><path class="clr-i-outline clr-i-outline-path-2 g2yqdbc5m"/><path class="clr-i-outline clr-i-outline-path-3 vcbrqcbbw"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:objects-line" /></template>
