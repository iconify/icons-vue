<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whlv7ub9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whlv7ub9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:outside" /></template>
