<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oocjo8pxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oocjo8pxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:radio1" /></template>
