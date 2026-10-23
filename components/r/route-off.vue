<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqo7pybtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqo7pybtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:route-off" /></template>
