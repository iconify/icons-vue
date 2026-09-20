<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxg05pb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxg05pb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:thingiverse" /></template>
