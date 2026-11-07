<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx4zoabor.css';
import '../../css/p/pm4bswxgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx4zoabor"/><path class="pm4bswxgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transfer-vertical-bold-duotone" /></template>
