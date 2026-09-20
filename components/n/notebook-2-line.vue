<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8q64_3nk.css';
import '../../css/k/kuvr68irh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8q64_3nk"/><path class="kuvr68irh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:notebook-2-line" /></template>
