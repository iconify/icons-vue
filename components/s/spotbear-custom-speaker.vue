<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwr-enbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwr-enbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:spotbear-custom-speaker" /></template>
