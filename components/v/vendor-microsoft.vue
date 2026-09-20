<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc8h3_bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc8h3_bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:vendor-microsoft" /></template>
