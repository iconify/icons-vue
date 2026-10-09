<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbv3grl-l.css';
import '../../css/i/idfrb-b4g.css';
import '../../css/k/kiditcb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jbv3grl-l"/><path class="idfrb-b4g"/><path class="kiditcb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:virtual-power-plant-20" /></template>
