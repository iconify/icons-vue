<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/l/lll-uetsu.css';
import '../../css/o/ovjw8ab9k.css';
import '../../css/i/ibejhacsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="lll-uetsu"/><path class="ovjw8ab9k"/><path class="ibejhacsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:open-access-logo" /></template>
