<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i16ny7bvz.css';
import '../../css/e/e3jspeiln.css';
import '../../css/d/duvqrbc-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i16ny7bvz"/><path class="e3jspeiln"/><path class="duvqrbc-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-tower-20" /></template>
