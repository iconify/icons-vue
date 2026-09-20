<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk4a8etro.css';
import '../../css/n/nwj7terdc.css';
import '../../css/l/lh639nb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk4a8etro"/><path class="nwj7terdc"/><path class="lh639nb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sort-numeric-down" /></template>
