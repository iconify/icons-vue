<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oao_97big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oao_97big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pillar-spot-3" /></template>
