<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/m/mcno18bmy.css';
import '../../css/i/i92g2uadp.css';
import '../../css/g/gtnoc3_rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="mcno18bmy"/><path class="i92g2uadp"/></g><path class="gtnoc3_rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:separator-vertical-bold-duotone" /></template>
