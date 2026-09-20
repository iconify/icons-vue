<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydovum.css';
import '../../css/y/yk2dha.css';
import '../../css/x/xopa8c.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-48.css';
import '../../css/t/tr-7ecuqx.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydovum yk2dha"/><circle class="xopa8c ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-twotone-loop" /></template>
