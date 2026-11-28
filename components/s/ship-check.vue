<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-rrwfb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-rrwfb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ship-check" /></template>
