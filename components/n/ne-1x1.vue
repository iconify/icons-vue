<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxpcs_bus.css';
import '../../css/n/ndyez317g.css';
import '../../css/o/o_qzz2bfh.css';
import '../../css/o/o5a6febyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cxpcs_bus"/><path class="ndyez317g"/><path class="o_qzz2bfh"/><circle class="o5a6febyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ne-1x1" /></template>
