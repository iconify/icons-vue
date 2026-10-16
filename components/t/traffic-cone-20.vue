<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chylptbbp.css';
import '../../css/l/lu03jdbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="chylptbbp"/><path class="lu03jdbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:traffic-cone-20" /></template>
