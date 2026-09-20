<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqx_ddk6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="iqx_ddk6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:pullquote" /></template>
