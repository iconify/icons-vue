<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkfdj_bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkfdj_bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-check" /></template>
