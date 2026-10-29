<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k84skwu6c.css';
import '../../css/o/of5os0b0n.css';
import '../../css/o/or-u2cczz.css';
import '../../css/h/h9d8qibbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k84skwu6c wm-k"/><path class="of5os0b0n wm-k"/><path class="or-u2cczz wm-a"/><path class="h9d8qibbo wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rangoli-pattern-sketch" /></template>
