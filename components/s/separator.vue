<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys9-2ab3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ys9-2ab3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:separator" /></template>
