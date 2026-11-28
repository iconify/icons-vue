<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv5_uvb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv5_uvb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sigma" /></template>
