<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh5sn9n9c.css';
import '../../css/d/d1xxgk97m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qh5sn9n9c"/><path class="d1xxgk97m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rack-and-pinion-20" /></template>
