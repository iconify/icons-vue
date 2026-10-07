<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt3no1brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt3no1brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubiquiti-ap" /></template>
