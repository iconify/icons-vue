<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2mx4lulm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2mx4lulm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:prowlarr" /></template>
