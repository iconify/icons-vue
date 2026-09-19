<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wztfgntmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wztfgntmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:sketch-solid" /></template>
