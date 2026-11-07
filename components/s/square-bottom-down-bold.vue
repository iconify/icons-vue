<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdnocya5g.css';
import '../../css/s/sfzfjg58s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hdnocya5g"/><path class="sfzfjg58s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-bottom-down-bold" /></template>
