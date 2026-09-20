<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv-4i2bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv-4i2bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:marquee-2" /></template>
