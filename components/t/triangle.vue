<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx97tgw1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx97tgw1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:triangle" /></template>
