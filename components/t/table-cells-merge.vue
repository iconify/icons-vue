<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pppd8hv8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pppd8hv8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:table-cells-merge" /></template>
