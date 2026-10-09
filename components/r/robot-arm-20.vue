<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy2ju-cra.css';
import '../../css/l/lqfl87oqj.css';
import '../../css/s/swlc9x42h.css';
import '../../css/w/w5iv359ji.css';
import '../../css/m/mtv6tabvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hy2ju-cra"/><path class="lqfl87oqj"/><path class="swlc9x42h"/><path class="w5iv359ji"/><path class="mtv6tabvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:robot-arm-20" /></template>
