<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ses441b-t.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lma1j-bkv.css';
import '../../css/w/wlqhkwbzb.css';
import '../../css/m/mc9a0ov5s.css';
import '../../css/y/yte00hbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary ses441b-t"/><g class="dt0cm9dhy primary"><path class="lma1j-bkv"/><path class="wlqhkwbzb"/><path class="mc9a0ov5s"/><path class="yte00hbxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:point-up-duo" /></template>
