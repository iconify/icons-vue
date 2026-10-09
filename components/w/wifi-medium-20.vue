<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw0wqacwc.css';
import '../../css/x/x0b3z4bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lw0wqacwc"/><path class="x0b3z4bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-medium-20" /></template>
