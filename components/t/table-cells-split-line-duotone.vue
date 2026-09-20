<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f_e3mnbwd.css';
import '../../css/b/b8504g80a.css';
import '../../css/m/myo_spbcy.css';
import '../../css/b/b2vvr6bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f_e3mnbwd"/><path class="b8504g80a"/><path class="myo_spbcy"/><path class="b2vvr6bvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-cells-split-line-duotone" /></template>
