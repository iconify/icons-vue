<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdv2lsgrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdv2lsgrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:washing-machine-clock" /></template>
