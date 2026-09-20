<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sphz-eb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sphz-eb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tourbox" /></template>
