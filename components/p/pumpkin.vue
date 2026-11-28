<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhpxstb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhpxstb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pumpkin" /></template>
