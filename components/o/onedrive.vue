<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcytv_bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcytv_bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:onedrive" /></template>
