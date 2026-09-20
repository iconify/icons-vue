<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv3ybibxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv3ybibxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-3-box-outline" /></template>
