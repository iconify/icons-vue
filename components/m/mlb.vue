<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xosmew7jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xosmew7jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mlb" /></template>
