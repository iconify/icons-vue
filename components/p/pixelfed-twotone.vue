<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo8cxy.css';
import '../../css/y/ydovum.css';
import '../../css/n/n6m-cw.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/f/fade-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo8cxy ydovum"/><path class="n6m-cw ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:pixelfed-twotone" /></template>
