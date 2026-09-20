<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_omvb_gj.css';
import '../../css/x/xgsv66jjz.css';
import '../../css/k/kg-qgmbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle clip-rule="evenodd" transform="rotate(-13.286 255.94 255.868)" class="k_omvb_gj"/><path clip-rule="evenodd" class="xgsv66jjz"/><path clip-rule="evenodd" class="kg-qgmbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-dark" /></template>
