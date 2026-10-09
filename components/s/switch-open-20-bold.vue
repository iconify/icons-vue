<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-cr1kbtc.css';
import '../../css/j/ji6lv2bxm.css';
import '../../css/a/aqsuay1um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t-cr1kbtc"/><path class="ji6lv2bxm"/><path class="aqsuay1um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:switch-open-20-bold" /></template>
