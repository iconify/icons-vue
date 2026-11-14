<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wxqivyo1u.css';
import '../../css/l/lx_r95vpd.css';
import '../../css/g/g1z1i765o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wxqivyo1u"/><ellipse class="lx_r95vpd"/><path class="g1z1i765o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:roaming" /></template>
