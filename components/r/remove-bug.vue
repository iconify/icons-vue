<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx_umsb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="yx_umsb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:remove-bug" /></template>
