<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t65xpx6zu.css';
import '../../css/p/psnhmojdp.css';
import '../../css/b/b8blzr_2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t65xpx6zu"/><path class="psnhmojdp"/><path class="b8blzr_2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-turbine-off-20" /></template>
