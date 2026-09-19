<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l15tcjb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l15tcjb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:shutter-20" /></template>
