<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qorl_g63f.css';
import '../../css/m/m2pt6cjck.css';
import '../../css/o/okdvo848h.css';
import '../../css/p/pycxazbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qorl_g63f"/><path class="m2pt6cjck"/><path class="okdvo848h"/><path class="pycxazbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offshore-hydrogen-20" /></template>
