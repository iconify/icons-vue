<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf2faab1e.css';
import '../../css/u/u-06obvoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf2faab1e"/><path class="u-06obvoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:radiobox-line" /></template>
