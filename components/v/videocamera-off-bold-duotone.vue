<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd4l-wycb.css';
import '../../css/p/prycr4uyu.css';
import '../../css/g/gn_f1tn5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd4l-wycb"/><path class="prycr4uyu"/><path class="gn_f1tn5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:videocamera-off-bold-duotone" /></template>
