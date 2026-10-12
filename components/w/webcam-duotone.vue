<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p2wr1lf8y.css';
import '../../css/n/n33v813cm.css';
import '../../css/u/uvm1-pvtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p2wr1lf8y"/><path class="n33v813cm"/><path clip-rule="evenodd" class="uvm1-pvtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:webcam-duotone" /></template>
