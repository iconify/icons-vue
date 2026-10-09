<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi9mw4qcx.css';
import '../../css/y/yz--wtxhz.css';
import '../../css/h/hubf0zbho.css';
import '../../css/b/bau81vnse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bi9mw4qcx"/><path class="yz--wtxhz"/><path class="hubf0zbho"/><path class="bau81vnse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scales-20-bold" /></template>
