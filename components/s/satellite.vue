<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtbx9gb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mtbx9gb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:satellite" /></template>
