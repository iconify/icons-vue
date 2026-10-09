<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj3g-36wb.css';
import '../../css/h/hoczzqb5s.css';
import '../../css/m/ml860nrta.css';
import '../../css/e/eqh2q3bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fj3g-36wb"/><path class="hoczzqb5s"/><path class="ml860nrta"/><path class="eqh2q3bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:multimeter-20" /></template>
