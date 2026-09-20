<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfo7_rqdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfo7_rqdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:verdaccio" /></template>
