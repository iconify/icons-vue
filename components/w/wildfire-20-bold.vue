<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyix3hqdx.css';
import '../../css/f/fqywsjpmm.css';
import '../../css/s/sv88clbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lyix3hqdx"/><path class="fqywsjpmm"/><path class="sv88clbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wildfire-20-bold" /></template>
