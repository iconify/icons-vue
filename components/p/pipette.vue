<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq2065bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq2065bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:pipette" /></template>
