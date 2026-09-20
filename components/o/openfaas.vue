<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weck2_bvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="weck2_bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openfaas" /></template>
