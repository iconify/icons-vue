<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z22c6ybkz.css';
import '../../css/x/xmr7_lblt.css';
import '../../css/m/mi661mi7p.css';
import '../../css/m/mk7wn8hfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z22c6ybkz"/><path class="xmr7_lblt"/><path class="mi661mi7p"/><path class="mk7wn8hfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-cooker-20" /></template>
