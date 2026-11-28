<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rixc3yb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rixc3yb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:printer-gear" /></template>
