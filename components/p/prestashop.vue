<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp15o-hmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp15o-hmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:prestashop" /></template>
