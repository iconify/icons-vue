<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppmm91byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppmm91byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-add-call-line" /></template>
