<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwbssxb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwbssxb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-selection" /></template>
