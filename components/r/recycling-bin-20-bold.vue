<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7css8qyx.css';
import '../../css/t/t3qrchbmg.css';
import '../../css/x/xlefwjb-d.css';
import '../../css/i/ii8kgdb-j.css';
import '../../css/l/lshrqm29f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u7css8qyx"/><path class="t3qrchbmg"/><path class="xlefwjb-d"/><path class="ii8kgdb-j"/><path class="lshrqm29f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:recycling-bin-20-bold" /></template>
