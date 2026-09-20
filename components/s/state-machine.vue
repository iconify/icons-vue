<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt4ijfdhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt4ijfdhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:state-machine" /></template>
