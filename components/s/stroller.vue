<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn0hxm-rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn0hxm-rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:stroller" /></template>
