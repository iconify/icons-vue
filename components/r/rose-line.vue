<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k08lv-bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k08lv-bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rose-line" /></template>
