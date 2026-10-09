<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rab_xlb9n.css';
import '../../css/q/qv1h0pygk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rab_xlb9n"/><path class="qv1h0pygk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wattmeter-20-bold" /></template>
