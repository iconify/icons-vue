<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hub5-1bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hub5-1bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:trending-up" /></template>
