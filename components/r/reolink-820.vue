<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg-yxldyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg-yxldyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:reolink-820" /></template>
