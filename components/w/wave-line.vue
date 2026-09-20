<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pms0pobwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pms0pobwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wave-line" /></template>
