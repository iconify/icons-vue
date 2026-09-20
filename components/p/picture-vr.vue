<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v96n9tbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v96n9tbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:picture-vr" /></template>
