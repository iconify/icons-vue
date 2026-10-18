<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c367unbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c367unbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:timer-off" /></template>
