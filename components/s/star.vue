<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orp0t1bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orp0t1bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:star" /></template>
