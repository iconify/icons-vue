<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sll1r44eb.css';
import '../../css/m/mr5-0kkhw.css';
import '../../css/c/cz6_nbepy.css';
import '../../css/p/pvctzfblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="sll1r44eb"/><path class="mr5-0kkhw"/><path class="cz6_nbepy"/><path class="pvctzfblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:pathology" /></template>
