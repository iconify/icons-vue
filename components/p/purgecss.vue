<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy9pv4mjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy9pv4mjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:purgecss" /></template>
