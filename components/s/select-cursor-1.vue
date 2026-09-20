<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ph-3zj5qm.css';
import '../../css/p/phy_y3bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="ph-3zj5qm"/><path clip-rule="evenodd" class="phy_y3bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:select-cursor-1" /></template>
